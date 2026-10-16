<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xszdr5bbz.css';
import '../../css/k/klmj08ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xszdr5bbz"/><path class="klmj08ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-rod-48-bold" /></template>
