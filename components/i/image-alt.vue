<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfbidkmpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="nfbidkmpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:image-alt" /></template>
