<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k3pi-5buh.css';
import '../../css/x/xi9sf57es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k3pi-5buh"/><path clip-rule="evenodd" class="xi9sf57es"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:filter-dollar-solid" /></template>
