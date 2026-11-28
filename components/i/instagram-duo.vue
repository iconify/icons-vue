<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl3hxibei.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/van__r8hm.css';
import '../../css/d/dutg3fb-n.css';
import '../../css/a/a09iknzhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tl3hxibei"/><g class="dt0cm9dhy primary"><path class="van__r8hm"/><path class="dutg3fb-n"/><path class="a09iknzhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:instagram-duo" /></template>
