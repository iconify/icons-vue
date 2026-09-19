<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8e9ji_ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="k8e9ji_ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-peace" /></template>
