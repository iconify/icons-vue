<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwstf9b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wwstf9b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:8-circle-fill" /></template>
