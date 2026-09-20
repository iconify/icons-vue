<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvhor06rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvhor06rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dashboard-1-solid" /></template>
