<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn340v__e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn340v__e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-rotation-angle-down" /></template>
