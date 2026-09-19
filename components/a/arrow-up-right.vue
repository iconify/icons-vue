<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaj3hvpiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaj3hvpiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-up-right" /></template>
