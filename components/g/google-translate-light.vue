<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxuo7eb7y.css';
import '../../css/g/gin1cnjoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uxuo7eb7y"/><path class="gin1cnjoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-translate-light" /></template>
