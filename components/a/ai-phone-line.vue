<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haxd8wxpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haxd8wxpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-phone-line" /></template>
