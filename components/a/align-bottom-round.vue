<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh-z7sdsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-z7sdsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-bottom-round" /></template>
