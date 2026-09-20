<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwdn4qbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwdn4qbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fruit-cherries-off" /></template>
