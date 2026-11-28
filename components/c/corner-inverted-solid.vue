<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvayf1bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvayf1bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-inverted-solid" /></template>
