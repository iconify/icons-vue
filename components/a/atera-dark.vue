<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-n1e2gul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-n1e2gul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atera-dark" /></template>
