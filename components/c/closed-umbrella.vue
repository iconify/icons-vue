<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h3fw97bqp.css';
import '../../css/q/q__pyacab.css';
import '../../css/z/z2qq6bcoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h3fw97bqp"/><path clip-rule="evenodd" class="q__pyacab"/><path class="z2qq6bcoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:closed-umbrella" /></template>
