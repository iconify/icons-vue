<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go9nm4qyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go9nm4qyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:between-horizontal-start-line" /></template>
