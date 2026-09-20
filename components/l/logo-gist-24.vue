<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueozdva-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":38,"height":24};
const content = `<path class="ueozdva-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:logo-gist-24" /></template>
