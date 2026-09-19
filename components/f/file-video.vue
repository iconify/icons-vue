<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrb8hk_en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qrb8hk_en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-video" /></template>
