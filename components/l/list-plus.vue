<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc1sal3cu.css';
import '../../css/y/yydzvbuei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc1sal3cu wm-k"/><path class="wm-s yydzvbuei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:list-plus" /></template>
