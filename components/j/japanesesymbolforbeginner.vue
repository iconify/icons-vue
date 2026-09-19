<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odn0cubmr.css';
import '../../css/k/kbgn2obeo.css';
import '../../css/f/fnb9a-75o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odn0cubmr"/><path class="kbgn2obeo"/><path class="fnb9a-75o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:japanesesymbolforbeginner" /></template>
