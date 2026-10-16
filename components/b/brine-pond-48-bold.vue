<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfk6c0bde.css';
import '../../css/a/alm7xj5_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kfk6c0bde"/><path class="alm7xj5_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brine-pond-48-bold" /></template>
