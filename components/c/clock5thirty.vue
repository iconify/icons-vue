<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt893gged.css';
import '../../css/e/eg39dacou.css';
import '../../css/r/rc5x6vdrd.css';
import '../../css/d/dsx4j5bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt893gged"/><path class="eg39dacou"/><path class="rc5x6vdrd"/><path class="dsx4j5bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clock5thirty" /></template>
