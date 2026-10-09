<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4vli7ncu.css';
import '../../css/q/qkvjsbbnn.css';
import '../../css/k/klpkadckn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4vli7ncu"/><path class="qkvjsbbnn"/><path class="klpkadckn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-donut-48-bold" /></template>
