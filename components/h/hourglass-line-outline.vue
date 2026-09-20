<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1jp5obwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1jp5obwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hourglass-line-outline" /></template>
