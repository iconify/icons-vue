<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebd7wrd7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebd7wrd7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gmail-dark" /></template>
