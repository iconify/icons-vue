<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqh5qzb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zqh5qzb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:laptop-code" /></template>
