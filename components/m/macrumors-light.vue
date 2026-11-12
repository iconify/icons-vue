<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh-l_-f6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fh-l_-f6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:macrumors-light" /></template>
