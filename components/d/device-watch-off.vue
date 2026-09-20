<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei1baibta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1baibta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-off" /></template>
