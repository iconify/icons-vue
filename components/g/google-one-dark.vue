<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7c9s3b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f7c9s3b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-one-dark" /></template>
