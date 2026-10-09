<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h09i3hbzu.css';
import '../../css/q/q_dqg26dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h09i3hbzu"/><path class="q_dqg26dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-left-48" /></template>
