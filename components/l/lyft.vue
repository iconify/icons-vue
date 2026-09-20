<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0un1ccyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b0un1ccyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:lyft" /></template>
