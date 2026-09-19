<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8fc5u6ec.css';
import '../../css/i/iiydukdos.css';
import '../../css/g/g4-28t0-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer t8fc5u6ec"/><path class="duoicon-secondary-layer iiydukdos"/><path class="duoicon-primary-layer g4-28t0-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:cloud-snow" /></template>
