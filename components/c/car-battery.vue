<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je_6zsb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je_6zsb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-battery" /></template>
