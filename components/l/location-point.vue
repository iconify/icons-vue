<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emes4vsnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emes4vsnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:location-point" /></template>
