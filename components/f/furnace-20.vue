<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1cfpg0nt.css';
import '../../css/l/lbw0b8b1k.css';
import '../../css/b/bdk_48bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g1cfpg0nt"/><path class="lbw0b8b1k"/><path class="bdk_48bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:furnace-20" /></template>
