<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nygqmabbq.css';
import '../../css/i/iwdb11t7s.css';
import '../../css/l/l7sdbnbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nygqmabbq"/><path class="iwdb11t7s"/><path class="l7sdbnbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:helideck-20" /></template>
