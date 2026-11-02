<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh9ctcajn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9ctcajn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-3-line" /></template>
