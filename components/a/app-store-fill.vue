<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3m40hbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3m40hbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:app-store-fill" /></template>
