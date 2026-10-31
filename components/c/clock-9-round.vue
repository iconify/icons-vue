<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zik2nzbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zik2nzbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-9-round" /></template>
