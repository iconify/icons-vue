<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muej_p33h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muej_p33h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-hexagon-solid" /></template>
