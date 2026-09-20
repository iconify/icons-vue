<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smkpeh00y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="smkpeh00y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-item-align-middle" /></template>
