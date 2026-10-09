<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhxatuodl.css';
import '../../css/m/medb0fb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lhxatuodl"/><path class="medb0fb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charity-20" /></template>
