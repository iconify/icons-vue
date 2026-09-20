<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-5x3pb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-5x3pb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:css3-filled" /></template>
