<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9kihqb-w.css';
import '../../css/y/y37rc1b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9kihqb-w"/><path class="y37rc1b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitcoin" /></template>
