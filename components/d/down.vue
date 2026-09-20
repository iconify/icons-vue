<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st62hbcbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="st62hbcbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:down" /></template>
