<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7ddn-9dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7ddn-9dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-left-filled" /></template>
