<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j8e8rbc6x.css';
import '../../css/n/nqrz7szok.css';
import '../../css/j/j6md0tpiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j8e8rbc6x"/><path class="nqrz7szok"/><path class="j6md0tpiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:certificate" /></template>
