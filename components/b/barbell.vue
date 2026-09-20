<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crcczxkda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crcczxkda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:barbell" /></template>
