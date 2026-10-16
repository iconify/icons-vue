<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjiicgwoi.css';
import '../../css/i/iqro0lbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wjiicgwoi"/><path class="iqro0lbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-pitch-48" /></template>
