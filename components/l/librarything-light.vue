<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tom2gdcyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tom2gdcyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librarything-light" /></template>
