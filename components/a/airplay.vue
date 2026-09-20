<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho2xlpbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho2xlpbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplay" /></template>
