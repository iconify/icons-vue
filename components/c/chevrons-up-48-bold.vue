<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pju4p0r6w.css';
import '../../css/n/n8yz9-5xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pju4p0r6w"/><path class="n8yz9-5xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-up-48-bold" /></template>
