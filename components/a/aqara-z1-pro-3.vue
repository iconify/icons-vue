<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s--lpjb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s--lpjb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-z1-pro-3" /></template>
