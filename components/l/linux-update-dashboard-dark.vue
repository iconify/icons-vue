<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrrtibxz.css';
import '../../css/f/fu6o8ac5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbrrtibxz"/><path class="fu6o8ac5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-update-dashboard-dark" /></template>
