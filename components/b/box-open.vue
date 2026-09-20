<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbr8hcbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pbr8hcbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:box-open" /></template>
