<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3nr2d6ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3nr2d6ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cycle" /></template>
