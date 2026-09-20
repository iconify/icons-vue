<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0w6r0vef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m0w6r0vef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:caret-left-square-filled" /></template>
