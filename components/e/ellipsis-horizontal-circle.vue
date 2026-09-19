<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilp8-kwbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilp8-kwbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-horizontal-circle" /></template>
