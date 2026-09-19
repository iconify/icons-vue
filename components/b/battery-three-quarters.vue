<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn2jg20aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="nn2jg20aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:battery-three-quarters" /></template>
