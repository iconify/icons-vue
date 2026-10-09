<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v26w1ttai.css';
import '../../css/h/hbqtujzwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v26w1ttai"/><path class="hbqtujzwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fries-48-bold" /></template>
