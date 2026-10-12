<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozw6d3b3f.css';
import '../../css/h/h2bmrpbsg.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ozw6d3b3f"/><path class="h2bmrpbsg"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-check-20" /></template>
