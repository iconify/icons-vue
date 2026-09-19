<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq8f7ztqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq8f7ztqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-alt-2" /></template>
