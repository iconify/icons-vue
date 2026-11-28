<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx6a9yb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx6a9yb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:balloon-heart" /></template>
