<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ooj9bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b2ooj9bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:computer-filled" /></template>
