<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t81o7zwgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t81o7zwgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:highlighter-accent" /></template>
