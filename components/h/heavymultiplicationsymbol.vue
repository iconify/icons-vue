<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw6dkcb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vw6dkcb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heavymultiplicationsymbol" /></template>
