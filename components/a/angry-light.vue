<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m7pevhgad.css';
import '../../css/p/pkphtfbdi.css';
import '../../css/a/a1ldf12-h.css';
import '../../css/m/ml61terwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="m7pevhgad"/><path class="pkphtfbdi"/><circle class="a1ldf12-h"/><circle class="ml61terwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:angry-light" /></template>
