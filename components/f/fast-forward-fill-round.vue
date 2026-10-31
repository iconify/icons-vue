<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aemn-9ejj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aemn-9ejj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fast-forward-fill-round" /></template>
