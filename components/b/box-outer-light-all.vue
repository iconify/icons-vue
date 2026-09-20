<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as7zp-tqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="as7zp-tqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-all" /></template>
