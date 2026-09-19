<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6x8okbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6x8okbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:headphone-fill" /></template>
