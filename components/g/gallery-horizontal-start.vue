<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyhpmm--v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhpmm--v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-horizontal-start" /></template>
