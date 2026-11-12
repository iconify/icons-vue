<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5ledtbof.css';
import '../../css/v/vtrz5wtxj.css';
import '../../css/m/mx9-r4b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5ledtbof"/><path class="vtrz5wtxj"/><path class="mx9-r4b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:leafwiki-dark" /></template>
