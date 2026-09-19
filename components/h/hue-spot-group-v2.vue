<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr9ok6bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr9ok6bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hue-spot-group-v2" /></template>
