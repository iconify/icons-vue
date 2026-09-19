<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-33urxjf.css';
import '../../css/v/v0dunlvta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-33urxjf"/><path class="v0dunlvta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-left-stroke-square-filled" /></template>
