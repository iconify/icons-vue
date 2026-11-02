<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bldn_f5bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bldn_f5bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egg-fill" /></template>
