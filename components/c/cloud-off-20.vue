<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_14drd-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j_14drd-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-off-20" /></template>
