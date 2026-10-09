<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe8xottkx.css';
import '../../css/w/wh1r03b-i.css';
import '../../css/k/k3lgfsb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qe8xottkx"/><path class="wh1r03b-i"/><path class="k3lgfsb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-cable-48-bold" /></template>
