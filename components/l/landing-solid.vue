<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q316_cceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q316_cceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:landing-solid" /></template>
