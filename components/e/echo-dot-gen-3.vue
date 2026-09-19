<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my5dueb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my5dueb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-dot-gen-3" /></template>
