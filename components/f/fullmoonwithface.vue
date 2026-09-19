<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfj231j0y.css';
import '../../css/a/ayfs0cb5s.css';
import '../../css/w/wdxqc5bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="sfj231j0y"/><path class="ayfs0cb5s"/><path class="wdxqc5bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fullmoonwithface" /></template>
