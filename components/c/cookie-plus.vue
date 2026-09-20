<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-xmagbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-xmagbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-plus" /></template>
