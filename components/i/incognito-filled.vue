<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpov2tb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpov2tb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:incognito-filled" /></template>
