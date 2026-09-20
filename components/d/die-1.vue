<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ags-gkbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ags-gkbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:die-1" /></template>
