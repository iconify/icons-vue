<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1fi5_bhd.css';
import '../../css/p/p7vazbcay.css';
import '../../css/e/ec7l8wh3f.css';
import '../../css/f/fdmzxwnqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u1fi5_bhd"/><path class="p7vazbcay"/><path class="ec7l8wh3f"/><path class="fdmzxwnqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ambulance-20-bold" /></template>
