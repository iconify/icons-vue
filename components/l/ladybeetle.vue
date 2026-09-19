<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omu70acdu.css';
import '../../css/x/x_6zwgo6p.css';
import '../../css/v/v23eax-8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omu70acdu"/><path class="x_6zwgo6p"/><path class="v23eax-8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ladybeetle" /></template>
