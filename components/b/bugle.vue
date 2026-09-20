<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrlen5bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrlen5bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bugle" /></template>
