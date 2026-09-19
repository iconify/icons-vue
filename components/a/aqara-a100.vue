<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8oew7wwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8oew7wwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-a100" /></template>
