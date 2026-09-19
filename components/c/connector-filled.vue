<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ico4pibau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ico4pibau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:connector-filled" /></template>
