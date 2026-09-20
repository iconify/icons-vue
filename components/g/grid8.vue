<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gft-esr-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gft-esr-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid8" /></template>
