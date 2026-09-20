<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guvmkgbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="guvmkgbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookheaven-dark" /></template>
