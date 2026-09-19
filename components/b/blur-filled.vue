<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r21hqhwrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r21hqhwrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:blur-filled" /></template>
