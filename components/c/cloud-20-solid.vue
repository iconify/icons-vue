<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bthd_yb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bthd_yb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-20-solid" /></template>
