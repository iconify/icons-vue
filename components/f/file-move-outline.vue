<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3hh_23yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3hh_23yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-move-outline" /></template>
