<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_zincina.css';
import '../../css/h/h1ltq8ifw.css';
import '../../css/g/g9gmjl-2d.css';
import '../../css/a/aja_aog3q.css';
import '../../css/s/spy7zkbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q_zincina"/><path class="h1ltq8ifw"/><circle class="g9gmjl-2d"/><circle class="aja_aog3q"/><path class="spy7zkbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:git-pull-request-outline" /></template>
