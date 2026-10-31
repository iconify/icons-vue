<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv751gbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv751gbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:help-fill-round" /></template>
