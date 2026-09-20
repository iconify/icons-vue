<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxgn3kbue.css';
import '../../css/h/h-c75yrdf.css';
import '../../css/g/g953mjzjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxgn3kbue"/><path class="h-c75yrdf"/><path class="g953mjzjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kherad-light" /></template>
