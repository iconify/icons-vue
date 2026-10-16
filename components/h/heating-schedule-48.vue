<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km_1fum4q.css';
import '../../css/s/s45evebmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="km_1fum4q"/><path class="s45evebmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heating-schedule-48" /></template>
