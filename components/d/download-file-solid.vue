<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm5w17bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qm5w17bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:download-file-solid" /></template>
