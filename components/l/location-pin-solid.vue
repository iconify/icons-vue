<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-e3s_b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-e3s_b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:location-pin-solid" /></template>
