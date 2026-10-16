<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iht0nqksq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iht0nqksq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-list-48-bold" /></template>
