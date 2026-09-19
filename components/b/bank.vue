<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8bbxr3ye.css';
import '../../css/i/i28ld-2jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8bbxr3ye duoicon-secondary-layer"/><path class="duoicon-primary-layer i28ld-2jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bank" /></template>
