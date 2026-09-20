<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm6fhrbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wm6fhrbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-money" /></template>
