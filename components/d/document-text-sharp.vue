<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw834mbpj.css';
import '../../css/t/tbo0rsbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bw834mbpj"/><path class="tbo0rsbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:document-text-sharp" /></template>
