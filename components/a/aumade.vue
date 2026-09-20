<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz9ljnb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qz9ljnb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:aumade" /></template>
