<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh1abjj4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mh1abjj4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:globe" /></template>
