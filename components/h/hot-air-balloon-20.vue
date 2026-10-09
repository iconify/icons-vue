<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn8593byb.css';
import '../../css/g/gdm6o-2_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wn8593byb"/><path class="gdm6o-2_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-air-balloon-20" /></template>
