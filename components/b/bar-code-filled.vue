<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm1r5-bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zm1r5-bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bar-code-filled" /></template>
