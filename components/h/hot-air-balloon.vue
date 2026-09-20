<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5hb59dkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5hb59dkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hot-air-balloon" /></template>
