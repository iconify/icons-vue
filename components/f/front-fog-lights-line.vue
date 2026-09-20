<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty4dirbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty4dirbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:front-fog-lights-line" /></template>
