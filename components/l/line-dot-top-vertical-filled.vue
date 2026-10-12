<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz7qxycvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz7qxycvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:line-dot-top-vertical-filled" /></template>
