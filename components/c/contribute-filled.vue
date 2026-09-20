<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inwdg37im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inwdg37im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:contribute-filled" /></template>
