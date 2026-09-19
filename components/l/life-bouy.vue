<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuzwqwb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="zuzwqwb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:life-bouy" /></template>
