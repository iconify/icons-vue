<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxsh7ebsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxsh7ebsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:edit-solid" /></template>
