<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4u4i6t9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4u4i6t9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dots-circle-horizontal" /></template>
