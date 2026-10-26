<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz3_v7_xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kz3_v7_xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:lock-open" /></template>
