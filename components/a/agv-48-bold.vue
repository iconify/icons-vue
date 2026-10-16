<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikhyofbzz.css';
import '../../css/a/ay4i28ssf.css';
import '../../css/a/a6rc3ubbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ikhyofbzz"/><path class="ay4i28ssf"/><path class="a6rc3ubbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:agv-48-bold" /></template>
