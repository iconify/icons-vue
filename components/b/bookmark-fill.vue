<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqys8njih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqys8njih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:bookmark-fill" /></template>
