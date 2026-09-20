<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiefo44df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiefo44df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bottle-tonic-outline" /></template>
