<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh1ivl7mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh1ivl7mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arow-to-up-fill" /></template>
