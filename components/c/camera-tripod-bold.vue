<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh6eqlk_e.css';
import '../../css/d/dqmh4gbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh6eqlk_e"/><path class="dqmh4gbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:camera-tripod-bold" /></template>
