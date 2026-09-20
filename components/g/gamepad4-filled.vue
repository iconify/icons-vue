<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wje5lcmcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wje5lcmcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad4-filled" /></template>
