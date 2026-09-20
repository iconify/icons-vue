<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhr---bpz.css';
import '../../css/h/h_4f1111a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhr---bpz"/><path class="h_4f1111a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-24" /></template>
