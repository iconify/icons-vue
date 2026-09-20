<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlwgpbcjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwgpbcjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cd-rom" /></template>
