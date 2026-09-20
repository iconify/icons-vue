<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcxszbbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wcxszbbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-dash-circle-large-head-bold" /></template>
