<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1t-cvl_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l1t-cvl_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-center-filled" /></template>
