<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnh_2wb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnh_2wb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-6-line" /></template>
