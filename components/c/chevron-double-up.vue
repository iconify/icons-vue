<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2-_juz8j.css';
import '../../css/t/ty71tpvsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k2-_juz8j"/><path class="ty71tpvsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-double-up" /></template>
