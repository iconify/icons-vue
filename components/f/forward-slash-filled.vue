<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asofcbeqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asofcbeqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward-slash-filled" /></template>
