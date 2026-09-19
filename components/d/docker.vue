<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_0lj959o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_0lj959o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:docker" /></template>
