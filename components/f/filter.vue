<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aalmtx25p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aalmtx25p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:filter" /></template>
