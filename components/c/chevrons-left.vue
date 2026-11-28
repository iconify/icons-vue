<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb0atybhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb0atybhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chevrons-left" /></template>
