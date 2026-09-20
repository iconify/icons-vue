<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njq90-bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njq90-bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-dimmer-30" /></template>
