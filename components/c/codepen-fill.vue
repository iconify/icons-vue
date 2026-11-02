<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sucw5zbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sucw5zbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:codepen-fill" /></template>
