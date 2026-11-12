<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9q3jccrn.css';
import '../../css/m/m920y4n8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9q3jccrn"/><path class="m920y4n8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghidra-light" /></template>
