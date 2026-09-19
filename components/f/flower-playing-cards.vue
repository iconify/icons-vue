<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/czbk68b1i.css';
import '../../css/a/af7v1pb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="czbk68b1i"/><path class="af7v1pb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:flower-playing-cards" /></template>
