<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb1cwzbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb1cwzbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-2-fill" /></template>
