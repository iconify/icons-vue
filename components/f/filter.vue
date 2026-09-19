<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-pmg79_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-pmg79_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:filter" /></template>
