<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb8ln3bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yb8ln3bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:gitlab" /></template>
