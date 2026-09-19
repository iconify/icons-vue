<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wssfh2qzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wssfh2qzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file" /></template>
