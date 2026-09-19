<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pefrpe-di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pefrpe-di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gem" /></template>
