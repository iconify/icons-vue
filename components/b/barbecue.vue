<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/scnjp3e5g.css';
import '../../css/b/bri85kbqp.css';
import '../../css/r/r5v9wkb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="scnjp3e5g"/><circle class="bri85kbqp"/><path class="r5v9wkb7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:barbecue" /></template>
