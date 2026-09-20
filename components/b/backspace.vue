<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzh3ahbvr.css';
import '../../css/f/f5tkpn2pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vzh3ahbvr"/><path class="f5tkpn2pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:backspace" /></template>
