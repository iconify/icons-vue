<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axwh6ggcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axwh6ggcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:jumpto" /></template>
