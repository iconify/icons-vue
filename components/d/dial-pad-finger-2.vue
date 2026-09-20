<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlb2ztnyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rlb2ztnyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dial-pad-finger-2" /></template>
