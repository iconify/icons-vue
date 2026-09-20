<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghf9fibui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghf9fibui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-slash" /></template>
