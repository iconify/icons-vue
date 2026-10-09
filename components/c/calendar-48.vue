<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pycxs8orj.css';
import '../../css/r/rmqrb06os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="rmqrb06os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-48" /></template>
