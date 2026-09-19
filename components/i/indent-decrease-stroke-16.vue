<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg7j_bbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mg7j_bbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:indent-decrease-stroke-16" /></template>
