<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm0xz1bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tm0xz1bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:link-filled" /></template>
