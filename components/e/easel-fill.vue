<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn2mq9eik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zn2mq9eik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:easel-fill" /></template>
