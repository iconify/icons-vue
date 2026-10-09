<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywju0hn3b.css';
import '../../css/l/lytqpepod.css';
import '../../css/o/ortt9nb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ywju0hn3b"/><path class="lytqpepod"/><path class="ortt9nb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:first-aid-20" /></template>
