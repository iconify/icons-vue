<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc9jhobin.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oszrj5blc.css';
import '../../css/i/inmwkd4ia.css';
import '../../css/b/brsnfwb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc9jhobin secondary"/><g class="dt0cm9dhy primary"><path class="oszrj5blc"/><path class="inmwkd4ia"/><path class="brsnfwb1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:intersect-duo" /></template>
