<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zen2agbyu.css';
import '../../css/i/icxodqbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="icxodqbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-gbt-48" /></template>
