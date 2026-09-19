<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trnf75eay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="trnf75eay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:lastfm-square" /></template>
