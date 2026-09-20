<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mszzedjss.css';
import '../../css/s/s5a196bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mszzedjss"/><path class="s5a196bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:dashboard" /></template>
