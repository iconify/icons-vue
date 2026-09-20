<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wip02dbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wip02dbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:driver-filled" /></template>
