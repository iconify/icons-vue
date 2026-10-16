<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgupoibyg.css';
import '../../css/k/krza2gbnk.css';
import '../../css/e/exrys5kfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgupoibyg"/><path class="krza2gbnk"/><path class="exrys5kfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-canopy-48" /></template>
