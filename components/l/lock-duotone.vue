<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jiyrhnkcn.css';
import '../../css/e/esf9wtdqe.css';
import '../../css/y/y4w4nvbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jiyrhnkcn"/><path class="esf9wtdqe"/><path class="y4w4nvbqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lock-duotone" /></template>
