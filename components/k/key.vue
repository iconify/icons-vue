<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm302v34r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nm302v34r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:key" /></template>
