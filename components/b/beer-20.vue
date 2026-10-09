<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2e3_lbdq.css';
import '../../css/v/vjq6vyoor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u2e3_lbdq"/><path class="vjq6vyoor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:beer-20" /></template>
