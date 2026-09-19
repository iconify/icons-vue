<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2qfjvb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="z2qfjvb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:battery-quarter" /></template>
