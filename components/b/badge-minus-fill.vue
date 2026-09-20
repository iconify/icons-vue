<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6sfflbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6sfflbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-minus-fill" /></template>
