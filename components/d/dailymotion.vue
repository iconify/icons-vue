<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhjrpzbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhjrpzbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dailymotion" /></template>
