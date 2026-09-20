<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t60g_5qhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t60g_5qhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forgejo-dark" /></template>
