<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iviu9lava.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iviu9lava"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplace-success" /></template>
