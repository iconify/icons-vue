<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjpy1hcup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjpy1hcup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-letter-spacing" /></template>
