<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaw2iacuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aaw2iacuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:export-filled" /></template>
