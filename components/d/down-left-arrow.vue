<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw0s58bcd.css';
import '../../css/i/imnugdlgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bw0s58bcd"/><path class="imnugdlgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:down-left-arrow" /></template>
