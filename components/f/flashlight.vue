<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv-2k5v_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv-2k5v_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flashlight" /></template>
