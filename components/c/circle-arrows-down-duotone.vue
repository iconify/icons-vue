<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i7kf2hbsh.css';
import '../../css/v/vyfrjvxaq.css';
import '../../css/p/p_yafhj5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i7kf2hbsh"/><path class="vyfrjvxaq"/><path class="p_yafhj5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrows-down-duotone" /></template>
