<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9mjsubkx.css';
import '../../css/q/qaip3db6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g9mjsubkx"/><path class="qaip3db6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bus-48-bold" /></template>
