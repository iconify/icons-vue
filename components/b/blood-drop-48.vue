<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsu7h-b-q.css';
import '../../css/s/sn3j5vz1q.css';
import '../../css/c/c4_zttl1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fsu7h-b-q"/><path class="sn3j5vz1q"/><path class="c4_zttl1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blood-drop-48" /></template>
