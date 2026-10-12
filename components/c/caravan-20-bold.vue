<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9yynmbhe.css';
import '../../css/g/g-xpidcsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c9yynmbhe"/><path class="g-xpidcsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caravan-20-bold" /></template>
