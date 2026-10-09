<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re19_f2ye.css';
import '../../css/u/um6ozge3g.css';
import '../../css/r/rcnrracia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="re19_f2ye"/><path class="um6ozge3g"/><path class="rcnrracia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-recovery-20" /></template>
