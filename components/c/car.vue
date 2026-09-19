<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzp-_w0hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzp-_w0hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:car" /></template>
