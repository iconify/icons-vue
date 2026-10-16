<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc-70lbob.css';
import '../../css/b/b-pvjkb6t.css';
import '../../css/m/mdegrtxcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vc-70lbob"/><path class="b-pvjkb6t"/><path class="mdegrtxcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-plant-alert-48-bold" /></template>
