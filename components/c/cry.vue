<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itdalbbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itdalbbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:cry" /></template>
