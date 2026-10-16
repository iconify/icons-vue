<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osomhcctt.css';
import '../../css/k/k7j-vcupp.css';
import '../../css/g/g-sjg9bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="osomhcctt"/><path class="k7j-vcupp"/><path class="g-sjg9bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emergency-exit-48" /></template>
