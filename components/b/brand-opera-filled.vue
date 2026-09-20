<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxbsks6my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxbsks6my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-opera-filled" /></template>
