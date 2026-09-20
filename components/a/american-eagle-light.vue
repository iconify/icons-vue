<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cck1czbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cck1czbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:american-eagle-light" /></template>
