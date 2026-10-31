<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_mk7bzxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_mk7bzxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-check-fill-round" /></template>
