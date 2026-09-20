<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq2r9vbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lq2r9vbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:checkbox-filled" /></template>
