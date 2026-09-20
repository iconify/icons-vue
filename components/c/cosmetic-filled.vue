<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0ac84bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0ac84bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cosmetic-filled" /></template>
