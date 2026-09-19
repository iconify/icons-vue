<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkyxqo7ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkyxqo7ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:apple" /></template>
