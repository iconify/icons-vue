<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6y08ddso.css';
import '../../css/q/qky_02hhd.css';
import '../../css/y/y7680abmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6y08ddso"/><path class="qky_02hhd"/><path class="y7680abmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fault-48-bold" /></template>
