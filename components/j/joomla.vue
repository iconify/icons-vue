<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdb8j2bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xdb8j2bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:joomla" /></template>
