<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eju1qufva.css';
import '../../css/q/qele91b3l.css';
import '../../css/h/hobc68bet.css';
import '../../css/v/vdnsg9ohj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="eju1qufva"/><path class="qele91b3l"/><circle class="hobc68bet"/><circle class="vdnsg9ohj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:android" /></template>
