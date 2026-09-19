<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q00u4lbrm.css';
import '../../css/q/q3ouhtb3r.css';
import '../../css/f/fv17wn2rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q00u4lbrm"/><circle class="q3ouhtb3r"/><path class="fv17wn2rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:baseball-outline" /></template>
