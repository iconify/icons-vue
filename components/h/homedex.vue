<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew16t5bon.css';
import '../../css/m/mfhjfna5c.css';
import '../../css/b/b3g89hl7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ew16t5bon"/><path class="mfhjfna5c"/><path class="b3g89hl7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homedex" /></template>
