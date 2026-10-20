<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp7d7nb3s.css';
import '../../css/v/vqqrrtxdj.css';
import '../../css/a/a0erdxoze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lp7d7nb3s"/><path class="vqqrrtxdj"/><path class="a0erdxoze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:joystick-20-bold" /></template>
