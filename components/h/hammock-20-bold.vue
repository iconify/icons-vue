<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq1tynbis.css';
import '../../css/s/s0b8obc_s.css';
import '../../css/a/ao1_9pbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dq1tynbis"/><path class="s0b8obc_s"/><path class="ao1_9pbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hammock-20-bold" /></template>
