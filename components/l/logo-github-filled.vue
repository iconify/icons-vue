<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pktd8hbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pktd8hbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-github-filled" /></template>
