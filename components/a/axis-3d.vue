<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrmmcx55c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrmmcx55c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:axis-3d" /></template>
