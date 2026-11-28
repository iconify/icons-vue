<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mohn2ccty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mohn2ccty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:guitar" /></template>
