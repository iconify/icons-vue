<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlukkybbv.css';
import '../../css/v/v11awfbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlukkybbv"/><path class="v11awfbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bug-48-bold" /></template>
