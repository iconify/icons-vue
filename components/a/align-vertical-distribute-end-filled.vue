<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrq6b7p1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrq6b7p1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-distribute-end-filled" /></template>
