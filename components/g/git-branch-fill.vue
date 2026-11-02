<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8a7vcc0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8a7vcc0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-fill" /></template>
