<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t74_ogbzo.css';
import '../../css/y/ykv4cf_5b.css';
import '../../css/g/gmorbsb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t74_ogbzo"/><path class="ykv4cf_5b"/><path class="gmorbsb7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dumbbell-duotone" /></template>
