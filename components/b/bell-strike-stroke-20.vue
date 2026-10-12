<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-73xxboi.css';
import '../../css/a/as12j9bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g-73xxboi"/><path class="as12j9bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bell-strike-stroke-20" /></template>
