<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd19typvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd19typvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:format-vertical-align-center" /></template>
