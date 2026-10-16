<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6t120hgc.css';
import '../../css/z/z84soivbf.css';
import '../../css/n/n2mrg8b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6t120hgc"/><path class="z84soivbf"/><path class="n2mrg8b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-x-20-bold" /></template>
