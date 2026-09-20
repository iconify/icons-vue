<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdoxw_b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdoxw_b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bookmark-check-solid" /></template>
