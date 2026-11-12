<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/givuv5kav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="givuv5kav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubecraft-light" /></template>
