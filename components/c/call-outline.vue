<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foxw_5bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foxw_5bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:call-outline" /></template>
