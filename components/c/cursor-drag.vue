<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb589rkmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb589rkmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cursor-drag" /></template>
