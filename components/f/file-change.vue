<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdh_y_bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bdh_y_bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:file-change" /></template>
