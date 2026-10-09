<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgrtu-b6i.css';
import '../../css/y/yft263tla.css';
import '../../css/i/iqd64138m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qgrtu-b6i"/><path class="yft263tla"/><path class="iqd64138m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hammock-48" /></template>
