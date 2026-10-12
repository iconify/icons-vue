<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt9zz1bdg.css';
import '../../css/k/k0w0kweqa.css';
import '../../css/j/j3bulgbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tt9zz1bdg"/><path class="k0w0kweqa"/><path class="j3bulgbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drum-48-bold" /></template>
