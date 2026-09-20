<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5kud9bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5kud9bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:argo-cd-dark" /></template>
