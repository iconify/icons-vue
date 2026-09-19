<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi4esybmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yi4esybmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:gem" /></template>
