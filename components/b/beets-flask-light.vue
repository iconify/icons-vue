<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9hmh0b9g.css';
import '../../css/u/ujufagbba.css';
import '../../css/s/s8i3jsm2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="f9hmh0b9g"/><path class="ujufagbba"/><path class="s8i3jsm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beets-flask-light" /></template>
