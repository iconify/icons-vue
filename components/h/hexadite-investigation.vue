<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msixm3byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="msixm3byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:hexadite-investigation" /></template>
