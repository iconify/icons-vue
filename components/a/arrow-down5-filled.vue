<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aegl_7xqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aegl_7xqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down5-filled" /></template>
