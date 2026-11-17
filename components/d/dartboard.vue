<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxm2nbkqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxm2nbkqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dartboard" /></template>
