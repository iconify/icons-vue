<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7mbl0bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7mbl0bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drawing" /></template>
