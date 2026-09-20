<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5nb-51af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5nb-51af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:digg-logo-block" /></template>
