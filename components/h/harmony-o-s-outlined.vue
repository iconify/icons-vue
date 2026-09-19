<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td58n_bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="td58n_bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:harmony-o-s-outlined" /></template>
