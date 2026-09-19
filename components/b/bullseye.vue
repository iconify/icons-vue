<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5a4u33sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="n5a4u33sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bullseye" /></template>
