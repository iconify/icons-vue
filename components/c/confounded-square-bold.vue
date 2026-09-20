<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwz5j43hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dwz5j43hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:confounded-square-bold" /></template>
