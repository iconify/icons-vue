<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyj6__bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyj6__bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fire" /></template>
