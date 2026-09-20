<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adqbg89ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adqbg89ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loop-left-ai-line" /></template>
