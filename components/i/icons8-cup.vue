<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny01ndbld.css';
import '../../css/q/q1m6kzbir.css';
import '../../css/m/mfb-umueb.css';
import '../../css/u/uvbrxut2r.css';
import '../../css/i/iocexdb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ny01ndbld"/><g class="q1m6kzbir"><path class="mfb-umueb"/><path class="uvbrxut2r"/></g><path class="iocexdb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:icons8-cup" /></template>
