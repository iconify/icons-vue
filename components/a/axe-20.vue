<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9km6db4h.css';
import '../../css/o/ozsetf5vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w9km6db4h"/><path class="ozsetf5vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:axe-20" /></template>
