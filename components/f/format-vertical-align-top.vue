<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifrgh_bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifrgh_bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-vertical-align-top" /></template>
