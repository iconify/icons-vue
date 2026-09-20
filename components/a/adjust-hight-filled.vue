<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_5_ixbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x_5_ixbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:adjust-hight-filled" /></template>
