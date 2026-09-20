<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gos7t18ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gos7t18ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chinese-knot-fill" /></template>
