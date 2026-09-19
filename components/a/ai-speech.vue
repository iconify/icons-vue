<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9vas5ago.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9vas5ago"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-speech" /></template>
