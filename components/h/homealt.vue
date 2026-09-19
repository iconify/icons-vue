<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaa2vpbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="xaa2vpbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:homealt" /></template>
