<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7gb4mbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7gb4mbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:flash-solid" /></template>
