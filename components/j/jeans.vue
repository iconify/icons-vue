<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqe1m0bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zqe1m0bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:jeans" /></template>
