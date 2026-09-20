<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb3vq1y9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb3vq1y9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:labex" /></template>
