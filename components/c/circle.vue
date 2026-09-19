<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcjb6ibjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jcjb6ibjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle" /></template>
