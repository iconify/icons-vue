<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzwzl0bzs.css';
import '../../css/t/te6at6blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzwzl0bzs"/><path class="te6at6blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lightbulb-sparkle-48" /></template>
