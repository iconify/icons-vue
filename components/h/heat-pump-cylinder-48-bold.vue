<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj475orgc.css';
import '../../css/t/th8tihb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mj475orgc"/><path class="th8tihb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-cylinder-48-bold" /></template>
