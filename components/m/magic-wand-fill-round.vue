<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh7nrubkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh7nrubkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magic-wand-fill-round" /></template>
