<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceecc4bcw.css';
import '../../css/d/d6cvwtbsp.css';
import '../../css/s/sadwe2bbu.css';
import '../../css/x/xivft9bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ceecc4bcw"/><path class="d6cvwtbsp"/><path class="sadwe2bbu"/><path class="xivft9bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biomethane-plant-48-bold" /></template>
