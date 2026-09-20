<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r12c-3b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r12c-3b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:convex" /></template>
