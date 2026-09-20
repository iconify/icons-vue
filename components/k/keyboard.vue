<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/artlz7bym.css';
import '../../css/c/c5y_3_b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="artlz7bym"/><path class="c5y_3_b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:keyboard" /></template>
