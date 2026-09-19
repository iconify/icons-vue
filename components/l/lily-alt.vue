<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eybkzfb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eybkzfb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lily-alt" /></template>
