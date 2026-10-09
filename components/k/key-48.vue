<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyg_4gbyx.css';
import '../../css/x/xua85z4wn.css';
import '../../css/p/petbblbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nyg_4gbyx"/><path class="xua85z4wn"/><path class="petbblbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-48" /></template>
