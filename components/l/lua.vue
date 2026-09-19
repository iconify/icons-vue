<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuu893b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nuu893b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lua" /></template>
