<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp64embkk.css';
import '../../css/i/i6zzx6b9n.css';
import '../../css/a/a56cl1b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rp64embkk"/><path class="i6zzx6b9n"/><path class="a56cl1b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:admissiontickets" /></template>
