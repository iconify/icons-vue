<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncr9o6bsk.css';
import '../../css/z/zegs8bbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncr9o6bsk"/><path class="zegs8bbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heartyellow" /></template>
