<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0rxk3bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0rxk3bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-edit" /></template>
