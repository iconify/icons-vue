<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6be-kb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a6be-kb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:labview" /></template>
