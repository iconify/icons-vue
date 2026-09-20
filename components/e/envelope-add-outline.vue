<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ll95seg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ll95seg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:envelope-add-outline" /></template>
