<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezw6blbcm.css';
import '../../css/p/pwe_-ab6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ezw6blbcm"/><path class="pwe_-ab6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cricket-48" /></template>
