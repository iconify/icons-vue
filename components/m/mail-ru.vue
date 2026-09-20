<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4dtxfgtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4dtxfgtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mail-ru" /></template>
