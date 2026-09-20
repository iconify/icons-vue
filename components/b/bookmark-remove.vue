<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltfo6yaen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="ltfo6yaen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bookmark-remove" /></template>
