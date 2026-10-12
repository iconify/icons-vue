<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i5i-6tbql.css';
import '../../css/h/hs2z7ejyy.css';
import '../../css/o/ob8610b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i5i-6tbql"/><path class="hs2z7ejyy"/><path class="ob8610b7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:joystick-duotone" /></template>
