<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuvrmqbix.css';
import '../../css/z/z2tgbdc9c.css';
import '../../css/q/q3_ql_27a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iuvrmqbix"/><path class="z2tgbdc9c"/><path class="q3_ql_27a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-flow-48" /></template>
