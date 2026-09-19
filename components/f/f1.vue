<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7gb9dbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7gb9dbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:f1" /></template>
