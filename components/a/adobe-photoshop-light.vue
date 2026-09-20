<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3ppw6pls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3ppw6pls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-photoshop-light" /></template>
