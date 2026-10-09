<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-0u49zj.css';
import '../../css/w/wh24nx91b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ok-0u49zj"/><path class="wh24nx91b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-bolt-48-bold" /></template>
