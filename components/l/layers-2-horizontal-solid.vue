<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-54k2y9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-54k2y9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-2-horizontal-solid" /></template>
