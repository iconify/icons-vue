<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyqpfl7lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyqpfl7lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:circle-stack" /></template>
