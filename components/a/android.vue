<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bi49tuoiu.css';
import '../../css/k/kzun96hrq.css';
import '../../css/i/icg4i3brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bi49tuoiu"/><circle class="kzun96hrq"/><circle class="icg4i3brj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:android" /></template>
