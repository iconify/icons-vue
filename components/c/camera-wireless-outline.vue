<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at19mqbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at19mqbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-wireless-outline" /></template>
