<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nac1dwsdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nac1dwsdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-maps-dark" /></template>
