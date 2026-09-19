<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otgpm3b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otgpm3b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:heart-dislike-outline" /></template>
