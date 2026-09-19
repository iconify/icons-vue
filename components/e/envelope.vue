<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtqmscb8b.css';
import '../../css/y/yujr8pbfe.css';
import '../../css/j/jpvlp2bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtqmscb8b"/><path class="yujr8pbfe"/><path class="jpvlp2bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:envelope" /></template>
