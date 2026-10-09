<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jukv1_4-a.css';
import '../../css/x/xoemm8bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jukv1_4-a"/><path class="xoemm8bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-container-48-bold" /></template>
