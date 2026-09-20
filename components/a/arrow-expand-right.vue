<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnzk5cc8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnzk5cc8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-expand-right" /></template>
