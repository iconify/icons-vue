<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpigsl5sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpigsl5sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-airplane" /></template>
