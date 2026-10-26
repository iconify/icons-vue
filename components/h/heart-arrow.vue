<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsg68bc0n.css';
import '../../css/b/bg8-v92az.css';
import '../../css/g/gsns-ke1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="bg8-v92az"/><path class="gsns-ke1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:heart-arrow" /></template>
