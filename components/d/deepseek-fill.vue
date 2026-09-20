<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as8ev18tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as8ev18tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:deepseek-fill" /></template>
