<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q6o7fihkv.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/r/ra6fhob8w.css';
import '../../css/s/sude8ublr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="q6o7fihkv"/><g class="mc2zb0bvp"><path class="ra6fhob8w"/><path class="sude8ublr"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-bold-duotone" /></template>
