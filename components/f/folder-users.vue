<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h6ho2ci2a.css';
import '../../css/v/vfr9osbmg.css';
import '../../css/v/vpqax4bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h6ho2ci2a"/><circle class="vfr9osbmg"/><path class="vpqax4bdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:folder-users" /></template>
