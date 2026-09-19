<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4ghfu6yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c4ghfu6yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:linux-mint" /></template>
