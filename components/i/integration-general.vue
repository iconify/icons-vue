<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk9ky-bpe.css';
import '../../css/q/qnu9x_btz.css';
import '../../css/q/qgw5s4bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="mk9ky-bpe"/><path class="qnu9x_btz"/><path clip-rule="evenodd" class="qgw5s4bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:integration-general" /></template>
