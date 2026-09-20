<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqkqm2b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qqkqm2b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:magic-wand-1" /></template>
