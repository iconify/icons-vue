<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc_77l01p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lc_77l01p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:container" /></template>
