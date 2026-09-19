<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_2dy2okx.css';
import '../../css/g/gc8-4tb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n_2dy2okx"/><path class="gc8-4tb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:down-square" /></template>
