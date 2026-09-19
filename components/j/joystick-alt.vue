<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alqc54g4m.css';
import '../../css/r/rn2kcz5al.css';
import '../../css/e/eo3krlb4g.css';
import '../../css/g/gnea6-e5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="alqc54g4m"/><circle class="rn2kcz5al"/><path class="eo3krlb4g"/><path class="gnea6-e5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:joystick-alt" /></template>
