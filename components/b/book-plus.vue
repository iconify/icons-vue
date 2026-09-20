<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx1v9mbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx1v9mbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-plus" /></template>
