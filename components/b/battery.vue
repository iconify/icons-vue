<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x68y6ab4a.css';
import '../../css/m/mgz8c9b8i.css';
import '../../css/u/u07nh0bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer x68y6ab4a"/><path class="duoicon-primary-layer mgz8c9b8i"/><path class="duoicon-secondary-layer u07nh0bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:battery" /></template>
