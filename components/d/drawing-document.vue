<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic-4bpbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ic-4bpbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:drawing-document" /></template>
