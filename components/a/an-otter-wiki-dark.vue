<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-y-mccno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-y-mccno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:an-otter-wiki-dark" /></template>
