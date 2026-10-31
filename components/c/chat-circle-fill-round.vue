<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2s2su-vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2s2su-vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-fill-round" /></template>
