<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayn4fno-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayn4fno-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:credit-card-bold" /></template>
