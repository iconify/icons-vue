<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1va1ac7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1va1ac7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jetblue-airways-dark" /></template>
