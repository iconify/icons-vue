<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wmcw7kbju.css';
import '../../css/x/xt31cgyzz.css';
import '../../css/k/kjbt3bbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wmcw7kbju"/><path class="xt31cgyzz"/><circle class="kjbt3bbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:eye-duotone" /></template>
