<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufflo816n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufflo816n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gamepad-directional" /></template>
