<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrw7cvbwr.css';
import '../../css/k/kqpp9twbz.css';
import '../../css/u/up9gopgdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrw7cvbwr"/><path class="kqpp9twbz"/><path class="up9gopgdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:capacitor-runtime-dark" /></template>
