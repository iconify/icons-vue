<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ik1jx-bvn.css';
import '../../css/v/vs10c0bmi.css';
import '../../css/n/n3yoqabcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ik1jx-bvn"/><path class="vs10c0bmi"/><path class="n3yoqabcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:home-duotone" /></template>
