<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3ac8-n2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3ac8-n2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fedex-light" /></template>
