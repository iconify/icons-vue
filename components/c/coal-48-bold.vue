<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu_d9ibfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lu_d9ibfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coal-48-bold" /></template>
