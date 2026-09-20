<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp-92zbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp-92zbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-f" /></template>
