<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb4ssgb7r.css';
import '../../css/e/eopyr_bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cb4ssgb7r"/><circle class="eopyr_bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:eye" /></template>
