<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lpg-xvqnb.css';
import '../../css/s/si6_izbqe.css';
import '../../css/b/bfe7iwbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lpg-xvqnb"/><path class="si6_izbqe"/><path class="bfe7iwbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hut" /></template>
