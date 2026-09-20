<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myl30ub-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myl30ub-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-alarm" /></template>
