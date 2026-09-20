<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejgmd2bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ejgmd2bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:container-hub-light" /></template>
