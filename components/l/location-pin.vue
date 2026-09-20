<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjtpz2b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jjtpz2b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:location-pin" /></template>
