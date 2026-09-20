<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpwqczfrc.css';
import '../../css/q/qas0_334r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpwqczfrc"/><path class="qas0_334r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:languagetool" /></template>
