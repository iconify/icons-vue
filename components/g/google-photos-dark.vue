<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1tbo-bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1tbo-bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-photos-dark" /></template>
