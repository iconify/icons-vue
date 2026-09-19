<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2n357b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r2n357b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:lgtm" /></template>
