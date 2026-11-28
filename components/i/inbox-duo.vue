<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmecobckr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bx22elb0t.css';
import '../../css/l/l7hat5ags.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmecobckr secondary"/><g class="dt0cm9dhy primary"><path class="bx22elb0t"/><path class="l7hat5ags"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:inbox-duo" /></template>
