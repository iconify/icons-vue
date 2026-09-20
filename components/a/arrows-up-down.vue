<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj99t9bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj99t9bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrows-up-down" /></template>
