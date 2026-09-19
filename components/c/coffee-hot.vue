<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18x4bbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="c18x4bbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:coffee-hot" /></template>
