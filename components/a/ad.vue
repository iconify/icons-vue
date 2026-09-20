<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk07qcbce.css';
import '../../css/u/uhu39ab7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk07qcbce"/><path class="uhu39ab7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:ad" /></template>
