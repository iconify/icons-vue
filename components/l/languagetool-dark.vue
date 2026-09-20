<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0dyagv-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0dyagv-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:languagetool-dark" /></template>
