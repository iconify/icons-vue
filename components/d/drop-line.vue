<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg6xq2bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg6xq2bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drop-line" /></template>
