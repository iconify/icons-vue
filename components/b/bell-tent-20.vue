<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhzmbr41b.css';
import '../../css/i/i1hgre67m.css';
import '../../css/s/sbqip972w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qhzmbr41b"/><path class="i1hgre67m"/><path class="sbqip972w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-tent-20" /></template>
