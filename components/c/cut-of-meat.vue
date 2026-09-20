<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz6gkrbil.css';
import '../../css/e/eqg4ddc9e.css';
import '../../css/f/foig20byy.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/y/yhga54b-i.css';
import '../../css/a/a731-2tvo.css';
import '../../css/g/g3pjqklsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fz6gkrbil"/><path class="eqg4ddc9e"/><circle class="foig20byy"/><g class="ij2x_72vy"><path class="yhga54b-i"/><path class="a731-2tvo"/><circle class="g3pjqklsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cut-of-meat" /></template>
