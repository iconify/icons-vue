<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdw6qmbbg.css';
import '../../css/k/kwyvscbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdw6qmbbg"/><path class="kwyvscbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cardboard-vr-line" /></template>
