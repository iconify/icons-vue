<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwkuroicc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qwkuroicc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:badge-shield-with-fire" /></template>
