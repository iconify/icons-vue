<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwcy0pbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwcy0pbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-arrow-down" /></template>
