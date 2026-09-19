<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-ge2ebrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-ge2ebrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-squint-tears" /></template>
