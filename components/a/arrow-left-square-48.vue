<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx2xmtbjn.css';
import '../../css/m/m3eum-q9t.css';
import '../../css/s/snfihfbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xx2xmtbjn"/><path class="m3eum-q9t"/><path class="snfihfbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-square-48" /></template>
