<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf0y-xe-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf0y-xe-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-top-alt-filled" /></template>
