<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsday64ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zsday64ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:batch-check-filled" /></template>
