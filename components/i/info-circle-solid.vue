<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tav20gbwz.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tav20gbwz"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:info-circle-solid" /></template>
