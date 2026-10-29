<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z56ok1bns.css';
import '../../css/w/wcpe8eb7b.css';
import '../../css/b/b4d1e6bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z56ok1bns"/><path class="wcpe8eb7b wm-a"/><path class="b4d1e6bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:car-front-duo" /></template>
