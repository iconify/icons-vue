<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nmf9j0bku.css';
import '../../css/o/oat20jbpp.css';
import '../../css/y/y_9bxsb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nmf9j0bku"/><path class="oat20jbpp"/><path class="y_9bxsb7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:donut2-duotone" /></template>
