<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxj7r4rhc.css';
import '../../css/x/x9cx8dvbi.css';
import '../../css/u/usalp6zbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxj7r4rhc"/><path class="x9cx8dvbi"/><path class="usalp6zbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:candy" /></template>
