<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id1bkk3ua.css';
import '../../css/g/g4zjvqbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="id1bkk3ua"/><path class="g4zjvqbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fishing-48" /></template>
