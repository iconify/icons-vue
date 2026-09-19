<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df57ckmtv.css';
import '../../css/d/df24pzbxt.css';
import '../../css/c/co_gutb3f.css';
import '../../css/m/mamssyaqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df57ckmtv"/><path class="df24pzbxt"/><path class="co_gutb3f"/><path class="mamssyaqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hourglassflowingsand" /></template>
