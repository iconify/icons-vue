<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw7vg6b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="zw7vg6b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:caret-right" /></template>
