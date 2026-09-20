<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxrr_ccra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxrr_ccra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-exit" /></template>
