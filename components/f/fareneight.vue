<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su-chh5bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="su-chh5bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:fareneight" /></template>
