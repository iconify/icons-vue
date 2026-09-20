<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j99-dtc4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j99-dtc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cooklang-chef-dark" /></template>
