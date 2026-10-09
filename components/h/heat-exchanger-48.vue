<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waw60ab1f.css';
import '../../css/c/cd-eh4cev.css';
import '../../css/b/b50gwx6hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="waw60ab1f"/><path class="cd-eh4cev"/><path class="b50gwx6hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-exchanger-48" /></template>
