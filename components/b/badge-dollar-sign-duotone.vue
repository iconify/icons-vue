<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fqj1yfbwj.css';
import '../../css/f/fbyge-9ve.css';
import '../../css/i/ilvo56ujz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fqj1yfbwj"/><path class="fbyge-9ve"/><path class="ilvo56ujz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-dollar-sign-duotone" /></template>
