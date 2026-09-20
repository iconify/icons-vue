<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9wu4-b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9wu4-b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:group-objects" /></template>
