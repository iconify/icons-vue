<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gklnstbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gklnstbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:editor-grid-lines" /></template>
