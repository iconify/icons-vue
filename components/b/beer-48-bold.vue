<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2p4lbbrb.css';
import '../../css/q/q0z4gbkbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z2p4lbbrb"/><path class="q0z4gbkbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:beer-48-bold" /></template>
