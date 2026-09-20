<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8-ciublm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8-ciublm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fast-forward-30" /></template>
