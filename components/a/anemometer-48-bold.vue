<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhvqtnbfx.css';
import '../../css/u/un5h_vbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uhvqtnbfx"/><path class="un5h_vbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anemometer-48-bold" /></template>
