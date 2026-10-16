<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o89debbzw.css';
import '../../css/l/lm68pefyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o89debbzw"/><path class="lm68pefyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-prismatic-48" /></template>
