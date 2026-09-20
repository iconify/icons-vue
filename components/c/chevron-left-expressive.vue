<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9m_iyplt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9m_iyplt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:chevron-left-expressive" /></template>
