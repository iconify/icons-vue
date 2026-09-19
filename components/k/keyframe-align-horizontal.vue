<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyqkuubta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyqkuubta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframe-align-horizontal" /></template>
