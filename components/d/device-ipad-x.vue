<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_fr24-nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_fr24-nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-x" /></template>
