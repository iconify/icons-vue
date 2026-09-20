<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rterafbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rterafbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-autonomous" /></template>
