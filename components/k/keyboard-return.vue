<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqle3ab3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqle3ab3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-return" /></template>
