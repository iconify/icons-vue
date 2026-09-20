<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhyzs1izz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhyzs1izz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docs-collaboration-dark" /></template>
