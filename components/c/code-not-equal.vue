<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvck6j57a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvck6j57a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-not-equal" /></template>
