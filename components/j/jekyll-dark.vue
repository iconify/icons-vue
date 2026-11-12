<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzg3y5byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xzg3y5byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jekyll-dark" /></template>
