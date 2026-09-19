<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhai6mw-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="yhai6mw-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:graduation-cap" /></template>
