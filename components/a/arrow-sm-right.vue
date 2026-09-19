<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx8n1l-fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx8n1l-fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-sm-right" /></template>
