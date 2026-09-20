<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_1wi8_tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g_1wi8_tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:file-deletion" /></template>
