<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slpu4qtxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slpu4qtxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-wind" /></template>
