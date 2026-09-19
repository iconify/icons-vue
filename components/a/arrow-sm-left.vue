<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilwl7-91o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilwl7-91o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-sm-left" /></template>
