<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7xqisbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-7};
const content = `<path class="e7xqisbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-down-left" /></template>
