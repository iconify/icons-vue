<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksaeh52hk.css';
import '../../css/u/uh3okxpvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksaeh52hk"/><path class="uh3okxpvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-phone-outgoing" /></template>
