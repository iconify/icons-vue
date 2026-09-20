<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgp09xbhr.css';
import '../../css/i/i1tveqj0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgp09xbhr"/><path class="i1tveqj0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flame-line" /></template>
