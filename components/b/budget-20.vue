<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szahujb-p.css';
import '../../css/g/gfv8n0rry.css';
import '../../css/c/c0xe9rb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="gfv8n0rry"/><path class="c0xe9rb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:budget-20" /></template>
