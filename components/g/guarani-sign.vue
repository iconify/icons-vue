<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk8pm6jyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="kk8pm6jyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:guarani-sign" /></template>
