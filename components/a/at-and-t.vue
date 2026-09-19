<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhh632bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bhh632bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:at-and-t" /></template>
