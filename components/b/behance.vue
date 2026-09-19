<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt2yctbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nt2yctbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:behance" /></template>
