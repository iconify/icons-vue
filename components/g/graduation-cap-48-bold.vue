<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnj1uyw7u.css';
import '../../css/j/jrg8o7ldv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xnj1uyw7u"/><path class="jrg8o7ldv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:graduation-cap-48-bold" /></template>
