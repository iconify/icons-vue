<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5ehemmsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="j5ehemmsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:battery-full" /></template>
