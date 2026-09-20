<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiwnp7bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uiwnp7bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:loaction2" /></template>
