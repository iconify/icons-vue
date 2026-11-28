<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b23un12lm.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/ciud1kn-e.css';
import '../../css/l/lcrewz3kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b23un12lm secondary"/><g class="dt0cm9dhy primary"><path class="ciud1kn-e"/><path class="lcrewz3kz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:duck-duo" /></template>
