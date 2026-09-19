<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2w2b3b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2w2b3b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-buffer-63" /></template>
