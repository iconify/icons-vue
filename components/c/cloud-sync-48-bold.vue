<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7plo0j7z.css';
import '../../css/c/crwtq5bps.css';
import '../../css/i/ijtbhzpet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w7plo0j7z"/><path class="crwtq5bps"/><path class="ijtbhzpet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sync-48-bold" /></template>
