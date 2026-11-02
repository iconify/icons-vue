<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_-lpel1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_-lpel1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-distribute-end-fill" /></template>
