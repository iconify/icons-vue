<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g86vpchlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="g86vpchlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-arrow-down" /></template>
