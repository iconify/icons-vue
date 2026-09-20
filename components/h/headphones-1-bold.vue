<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy26aup1d.css';
import '../../css/w/w5x0zccyo.css';
import '../../css/k/kv7e38bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy26aup1d"/><path class="w5x0zccyo"/><path class="kv7e38bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:headphones-1-bold" /></template>
