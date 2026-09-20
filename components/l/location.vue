<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/d/d-8w03bro.css';
import '../../css/h/hrjfpsb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 2)" class="jtowsomii"><path class="d-8w03bro"/><circle class="hrjfpsb2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:location" /></template>
