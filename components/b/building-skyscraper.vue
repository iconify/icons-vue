<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wttt595uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wttt595uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-skyscraper" /></template>
