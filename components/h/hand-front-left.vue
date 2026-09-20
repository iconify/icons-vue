<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8tmofbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8tmofbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-front-left" /></template>
