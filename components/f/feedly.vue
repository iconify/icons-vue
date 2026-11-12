<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3j8a4h1u.css';
import '../../css/r/r3b4dgb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3j8a4h1u"/><path class="r3b4dgb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feedly" /></template>
