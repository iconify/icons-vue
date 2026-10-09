<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2lgj0dvw.css';
import '../../css/y/ylt16dbqe.css';
import '../../css/i/i2exa8tnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v2lgj0dvw"/><path class="ylt16dbqe"/><path class="i2exa8tnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:guitar-48-bold" /></template>
