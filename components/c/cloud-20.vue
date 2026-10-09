<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzjn5iovv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xzjn5iovv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-20" /></template>
