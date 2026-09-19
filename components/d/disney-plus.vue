<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykweqzbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykweqzbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:disney-plus" /></template>
