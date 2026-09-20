<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w1lxsfucb.css';
import '../../css/k/k0evexoqr.css';
import '../../css/l/l606hpblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w1lxsfucb"/><circle class="k0evexoqr"/><circle class="l606hpblz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:insta" /></template>
