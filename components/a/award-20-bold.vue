<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tydcr7btg.css';
import '../../css/k/krbzztkfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tydcr7btg"/><path class="krbzztkfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:award-20-bold" /></template>
