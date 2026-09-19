<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig42f6box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig42f6box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:exclamation-circle" /></template>
