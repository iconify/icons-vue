<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3hzk0bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="o3hzk0bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:car-crash" /></template>
