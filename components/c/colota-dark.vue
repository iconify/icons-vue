<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b103epbdu.css';
import '../../css/v/v4-7tcbbz.css';
import '../../css/j/jtgp3g1cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b103epbdu"/><path class="v4-7tcbbz"/><path class="jtgp3g1cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:colota-dark" /></template>
