<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnk3igu_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk3igu_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlehome" /></template>
