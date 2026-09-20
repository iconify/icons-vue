<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw7oynbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uw7oynbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lemmy-dark" /></template>
