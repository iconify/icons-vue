<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4w-xccke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4w-xccke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:login" /></template>
