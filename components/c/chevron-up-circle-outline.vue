<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mujcmz6vw.css';
import '../../css/q/q-tflgzje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mujcmz6vw"/><path class="q-tflgzje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-up-circle-outline" /></template>
