<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3mfcsb3n.css';
import '../../css/s/snd_4ib6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z3mfcsb3n"/><path class="snd_4ib6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:car-key-48-bold" /></template>
