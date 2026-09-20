<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laf-l4e5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laf-l4e5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-gamepad-3" /></template>
