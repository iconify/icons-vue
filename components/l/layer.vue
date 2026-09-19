<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-jo3d9_a.css';
import '../../css/f/f7bx2zbyl.css';
import '../../css/w/wlr77q6kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-jo3d9_a"/><path class="f7bx2zbyl"/><path class="wlr77q6kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:layer" /></template>
