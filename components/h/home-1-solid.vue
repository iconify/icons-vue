<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlld55b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlld55b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:home-1-solid" /></template>
