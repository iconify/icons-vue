<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp2j194ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tp2j194ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudinary-light" /></template>
