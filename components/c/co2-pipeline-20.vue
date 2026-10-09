<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv6_rebxi.css';
import '../../css/a/ak3pdnn1p.css';
import '../../css/s/sv8sqhg9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iv6_rebxi"/><path class="ak3pdnn1p"/><path class="sv8sqhg9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-pipeline-20" /></template>
