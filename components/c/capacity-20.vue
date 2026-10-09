<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swnxxbo0p.css';
import '../../css/l/l4yoqg4nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="swnxxbo0p"/><path class="l4yoqg4nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:capacity-20" /></template>
