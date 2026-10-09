<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl8q1nb4n.css';
import '../../css/l/l5kfglbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wl8q1nb4n"/><path class="l5kfglbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-vertical-20" /></template>
