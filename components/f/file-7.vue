<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc0uk0c4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rc0uk0c4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-7" /></template>
