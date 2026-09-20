<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl1padfwm.css';
import '../../css/j/j2w1i02yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1padfwm"/><path class="j2w1i02yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-triangle-duotone" /></template>
