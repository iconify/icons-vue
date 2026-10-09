<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-v3z0_fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-v3z0_fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-20" /></template>
