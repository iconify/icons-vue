<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-y8ulbyu.css';
import '../../css/x/xovy7qr-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g-y8ulbyu"/><path class="xovy7qr-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-sink-48-bold" /></template>
