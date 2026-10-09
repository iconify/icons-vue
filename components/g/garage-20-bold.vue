<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlqdhacda.css';
import '../../css/o/ojpm0hbkb.css';
import '../../css/p/p7necabgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xlqdhacda"/><path class="ojpm0hbkb"/><path class="p7necabgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:garage-20-bold" /></template>
