<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqa01_boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqa01_boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-wifi-filled" /></template>
