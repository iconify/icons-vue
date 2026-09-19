<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akbj3-3cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akbj3-3cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevron-left" /></template>
