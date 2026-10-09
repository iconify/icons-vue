<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f12oouk3n.css';
import '../../css/k/kl112gs4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f12oouk3n"/><path class="kl112gs4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carabiner-20-bold" /></template>
