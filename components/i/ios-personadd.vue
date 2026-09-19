<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/temjivdtd.css';
import '../../css/e/e3yi-0i_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="temjivdtd"/><path class="e3yi-0i_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-personadd" /></template>
