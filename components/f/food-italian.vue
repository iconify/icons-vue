<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh4kocbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh4kocbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-italian" /></template>
