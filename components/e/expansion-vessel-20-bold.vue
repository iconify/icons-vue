<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkp57tl3g.css';
import '../../css/d/dhq72bbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pkp57tl3g"/><path class="dhq72bbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:expansion-vessel-20-bold" /></template>
