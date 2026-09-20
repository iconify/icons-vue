<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epmjb9o9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epmjb9o9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-right-large-light" /></template>
