<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2be4teex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2be4teex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:comment-medical" /></template>
