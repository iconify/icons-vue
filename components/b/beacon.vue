<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt6nh0b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt6nh0b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beacon" /></template>
