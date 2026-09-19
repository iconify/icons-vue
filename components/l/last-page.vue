<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0e22bbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0e22bbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:last-page" /></template>
