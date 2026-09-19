<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ubtkb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ubtkb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-down-small" /></template>
