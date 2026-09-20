<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2b9ambve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2b9ambve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flag-off-fill" /></template>
