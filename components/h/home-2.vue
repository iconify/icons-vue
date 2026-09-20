<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2-2zhbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2-2zhbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:home-2" /></template>
