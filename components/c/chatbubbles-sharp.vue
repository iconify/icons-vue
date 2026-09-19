<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugoumwb4c.css';
import '../../css/c/cfmtxnb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugoumwb4c"/><path class="cfmtxnb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chatbubbles-sharp" /></template>
