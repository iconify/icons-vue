<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eua6ogqea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eua6ogqea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:installatron-dark" /></template>
