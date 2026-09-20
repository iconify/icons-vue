<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4guqms_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4guqms_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-allo" /></template>
