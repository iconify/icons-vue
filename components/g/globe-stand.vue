<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-ltem8ez.css';
import '../../css/p/p-0vs8b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ltem8ez"/><path class="p-0vs8b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-stand" /></template>
