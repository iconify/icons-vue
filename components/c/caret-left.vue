<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nytsrmb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="nytsrmb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:caret-left" /></template>
