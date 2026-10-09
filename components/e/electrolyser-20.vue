<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cozw5lxrq.css';
import '../../css/w/wkvt3obva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cozw5lxrq"/><path class="wkvt3obva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electrolyser-20" /></template>
