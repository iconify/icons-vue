<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsp7zgb3m.css';
import '../../css/w/wo7e92b0f.css';
import '../../css/m/min81mbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fsp7zgb3m"/><path class="wo7e92b0f"/><path class="min81mbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dna-20-bold" /></template>
