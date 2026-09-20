<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgt9us2kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgt9us2kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chromecast" /></template>
