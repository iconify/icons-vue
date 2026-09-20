<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxqmg7esw.css';
import '../../css/s/s7gdozb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kxqmg7esw"/><path class="s7gdozb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:lightbulb" /></template>
