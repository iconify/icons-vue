<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g8qfvnbjm.css';
import '../../css/e/egfs-cciu.css';
import '../../css/z/zga1a2bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="g8qfvnbjm"/><circle class="egfs-cciu"/><path class="zga1a2bdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-lens" /></template>
