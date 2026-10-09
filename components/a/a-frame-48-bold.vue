<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzb20mb_q.css';
import '../../css/i/ip69v-b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bzb20mb_q"/><path class="ip69v-b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:a-frame-48-bold" /></template>
