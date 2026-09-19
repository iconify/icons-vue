<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esyyvmbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esyyvmbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:abc-australia-news" /></template>
