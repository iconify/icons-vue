<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqwjjpbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqwjjpbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filter-bold" /></template>
