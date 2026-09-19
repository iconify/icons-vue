<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir9h4mb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ir9h4mb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-filled" /></template>
