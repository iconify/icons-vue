<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9to7_n9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9to7_n9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up" /></template>
