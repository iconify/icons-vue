<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wibl5e4hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wibl5e4hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desklamp" /></template>
