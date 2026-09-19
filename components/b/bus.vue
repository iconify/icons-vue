<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aop2s9bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":746};
const content = `<path class="aop2s9bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bus" /></template>
