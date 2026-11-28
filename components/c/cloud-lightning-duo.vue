<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm6y7qboy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/txf_xf5pi.css';
import '../../css/m/myy3teiet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm6y7qboy secondary"/><g class="dt0cm9dhy primary"><path class="txf_xf5pi"/><path class="myy3teiet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-lightning-duo" /></template>
