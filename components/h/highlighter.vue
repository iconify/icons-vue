<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw4rwyb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="nw4rwyb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:highlighter" /></template>
