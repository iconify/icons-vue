<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ustd-of_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ustd-of_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:download" /></template>
