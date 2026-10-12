<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_yowkbgo.css';
import '../../css/l/lgdstuzsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c_yowkbgo"/><path class="lgdstuzsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:binder-48-bold" /></template>
