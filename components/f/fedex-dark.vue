<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww0y7wbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ww0y7wbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fedex-dark" /></template>
