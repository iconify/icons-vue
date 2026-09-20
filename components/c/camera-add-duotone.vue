<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/czat0q-qi.css';
import '../../css/h/hkpwmqo7k.css';
import '../../css/m/m6yu4qj4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="czat0q-qi"/><path clip-rule="evenodd" class="hkpwmqo7k"/><path class="m6yu4qj4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-add-duotone" /></template>
