<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg57_081g.css';
import '../../css/a/an7n-_bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xg57_081g"/><path class="an7n-_bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:babel" /></template>
