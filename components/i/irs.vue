<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-_hrufzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-_hrufzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:irs" /></template>
