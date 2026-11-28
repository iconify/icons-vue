<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkb1cls-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkb1cls-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:alarm-snooze-solid" /></template>
