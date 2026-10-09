<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjpipuzmt.css';
import '../../css/g/g73cn62ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjpipuzmt"/><path class="g73cn62ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:doorbell-48" /></template>
