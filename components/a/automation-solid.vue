<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0-nmgbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0-nmgbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:automation-solid" /></template>
