<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqsbp8b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqsbp8b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:christmas-tree-off" /></template>
