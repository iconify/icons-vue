<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ilb7ewq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ilb7ewq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-9-solid" /></template>
