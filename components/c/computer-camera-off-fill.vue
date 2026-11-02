<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fga-cy2vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fga-cy2vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-camera-off-fill" /></template>
