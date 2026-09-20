<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs8_5cw0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs8_5cw0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fatrows-filled" /></template>
