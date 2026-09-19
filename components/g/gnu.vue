<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shu7q-blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="shu7q-blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gnu" /></template>
