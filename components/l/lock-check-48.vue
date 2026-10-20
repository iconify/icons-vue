<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th_2c0ilx.css';
import '../../css/n/nv4ijsbik.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="th_2c0ilx"/><path class="nv4ijsbik"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-check-48" /></template>
