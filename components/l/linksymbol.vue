<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgpc5ebjb.css';
import '../../css/r/r8_pblidm.css';
import '../../css/y/yp3yrlb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgpc5ebjb"/><path class="r8_pblidm"/><path class="yp3yrlb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:linksymbol" /></template>
