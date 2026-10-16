<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2mjsubix.css';
import '../../css/b/bkl1c0rno.css';
import '../../css/k/kp5hxh01s.css';
import '../../css/b/bol9gfbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="bkl1c0rno"/><path class="kp5hxh01s"/><path class="bol9gfbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-gas-48-bold" /></template>
