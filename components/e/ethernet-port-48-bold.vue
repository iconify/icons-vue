<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-ykpjboh.css';
import '../../css/w/w-yr_fb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j-ykpjboh"/><path class="w-yr_fb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ethernet-port-48-bold" /></template>
