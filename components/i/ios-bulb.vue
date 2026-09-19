<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbexcdcsc.css';
import '../../css/b/btxln4pbg.css';
import '../../css/p/p8qjm6bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbexcdcsc"/><path class="btxln4pbg"/><path class="p8qjm6bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bulb" /></template>
