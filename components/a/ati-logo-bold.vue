<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwaanvb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwaanvb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ati-logo-bold" /></template>
