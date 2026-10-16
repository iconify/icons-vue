<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcia1ds6l.css';
import '../../css/i/istrjj4et.css';
import '../../css/y/y06ocpbjt.css';
import '../../css/p/pw9j91bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="istrjj4et"/><path class="y06ocpbjt"/><path class="pw9j91bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-environment-20-bold" /></template>
