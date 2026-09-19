<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0a_jacfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":434,"height":512};
const content = `<path clip-rule="evenodd" class="p0a_jacfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lfe" /></template>
