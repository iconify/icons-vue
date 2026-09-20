<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_hy-bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ck_hy-bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-up-left-box" /></template>
