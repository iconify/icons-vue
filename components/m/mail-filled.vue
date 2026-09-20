<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye28mvbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ye28mvbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mail-filled" /></template>
