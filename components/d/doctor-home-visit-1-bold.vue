<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzzun0bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzzun0bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:doctor-home-visit-1-bold" /></template>
