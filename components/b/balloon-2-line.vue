<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3jgqmb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3jgqmb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:balloon-2-line" /></template>
