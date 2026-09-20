<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyz8y5c5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyz8y5c5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-list" /></template>
