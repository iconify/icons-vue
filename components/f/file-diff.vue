<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx5subbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx5subbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-diff" /></template>
