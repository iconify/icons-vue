<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re7f0xsad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re7f0xsad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bridge" /></template>
