<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k8mndubwj.css';
import '../../css/n/nnrwljozc.css';
import '../../css/i/ihvzllbyi.css';
import '../../css/m/m_uwjcbrw.css';
import '../../css/p/pkrnwtb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="k8mndubwj"/><path class="nnrwljozc"/><path class="ihvzllbyi"/><path class="m_uwjcbrw"/><path class="pkrnwtb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:factory" /></template>
