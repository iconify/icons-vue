<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv0mj9bsl.css';
import '../../css/x/xbmduob_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="cv0mj9bsl"/><path class="xbmduob_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:camera" /></template>
