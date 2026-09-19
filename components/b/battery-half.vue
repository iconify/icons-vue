<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gstxg1kyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="gstxg1kyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:battery-half" /></template>
