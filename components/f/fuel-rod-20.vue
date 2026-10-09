<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhslc-sys.css';
import '../../css/b/be_b20boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rhslc-sys"/><path class="be_b20boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-rod-20" /></template>
