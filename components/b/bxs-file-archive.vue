<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq8k_v7yc.css';
import '../../css/r/relvolb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq8k_v7yc"/><path class="relvolb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-archive" /></template>
