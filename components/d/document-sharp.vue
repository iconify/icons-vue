<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqi-7acky.css';
import '../../css/b/bw834mbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqi-7acky"/><path class="bw834mbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:document-sharp" /></template>
