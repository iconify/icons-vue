<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no--2obox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no--2obox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-360-outline" /></template>
