<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5_t91bys.css';
import '../../css/b/bcu-xw_8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5_t91bys"/><path class="bcu-xw_8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-48-bold" /></template>
