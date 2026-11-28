<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aupjr3o0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aupjr3o0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:camera-solid" /></template>
