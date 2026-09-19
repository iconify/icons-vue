<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnht1tg6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnht1tg6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:action-undo" /></template>
