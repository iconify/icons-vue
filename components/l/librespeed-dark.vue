<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec5wcebee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec5wcebee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librespeed-dark" /></template>
