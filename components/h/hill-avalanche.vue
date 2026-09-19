<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnl_elb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cnl_elb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hill-avalanche" /></template>
