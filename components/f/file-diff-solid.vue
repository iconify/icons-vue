<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsnipk2fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsnipk2fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-diff-solid" /></template>
