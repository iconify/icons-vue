<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clw-feb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clw-feb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-face-solid" /></template>
