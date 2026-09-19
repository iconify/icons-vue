<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt893gged.css';
import '../../css/e/eg39dacou.css';
import '../../css/f/fd1dolbaw.css';
import '../../css/o/ooqsfwumf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt893gged"/><path class="eg39dacou"/><path class="fd1dolbaw"/><path class="ooqsfwumf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clock6oclock" /></template>
