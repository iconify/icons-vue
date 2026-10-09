<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xexqeacnw.css';
import '../../css/m/mpc5lgr0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xexqeacnw"/><path class="mpc5lgr0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-to-line-48-bold" /></template>
