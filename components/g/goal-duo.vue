<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la0_fqkid.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/ktnqlxbec.css';
import '../../css/y/yn5fphbsc.css';
import '../../css/o/o36i6xwrw.css';
import '../../css/m/m79smdbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la0_fqkid secondary"/><g class="dt0cm9dhy primary"><path class="ktnqlxbec"/><path class="yn5fphbsc"/><path class="o36i6xwrw"/><path class="m79smdbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:goal-duo" /></template>
