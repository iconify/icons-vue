<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct-exp8sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ct-exp8sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:circle-close-o" /></template>
