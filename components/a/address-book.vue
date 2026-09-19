<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd8fe119i.css';
import '../../css/q/qk5s2wd5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cd8fe119i"/><path class="qk5s2wd5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:address-book" /></template>
