<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvr0gmblg.css';
import '../../css/o/od6unwbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvr0gmblg"/><path class="od6unwbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:keyboard" /></template>
