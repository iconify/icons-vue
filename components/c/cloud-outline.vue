<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pahppx3dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pahppx3dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:cloud-outline" /></template>
