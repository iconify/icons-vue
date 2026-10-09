<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkze5mbgn.css';
import '../../css/v/vkaih402o.css';
import '../../css/w/wqgk4rban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkze5mbgn"/><path class="vkaih402o"/><path class="wqgk4rban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:butterfly-48-bold" /></template>
