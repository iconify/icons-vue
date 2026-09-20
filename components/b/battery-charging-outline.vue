<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh4z9dqco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh4z9dqco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-outline" /></template>
