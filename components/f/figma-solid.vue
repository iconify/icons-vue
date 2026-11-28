<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiku2ln1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiku2ln1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:figma-solid" /></template>
