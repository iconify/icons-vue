<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ix9hdebim.css';
import '../../css/q/q2875sbpw.css';
import '../../css/u/uvtbonwqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ix9hdebim"/><path class="q2875sbpw"/><path class="uvtbonwqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloudy-duotone" /></template>
