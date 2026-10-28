<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9gh3cbby.css';
import '../../css/g/gljjdb6ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9gh3cbby"/><path class="gljjdb6ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flux-operator" /></template>
