<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c822n_byc.css';
import '../../css/j/jtxyyikiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c822n_byc"/><path class="jtxyyikiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buggregator" /></template>
