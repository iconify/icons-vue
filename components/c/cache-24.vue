<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-6yb6bfg.css';
import '../../css/x/xxr0q9bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-6yb6bfg"/><path class="xxr0q9bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cache-24" /></template>
