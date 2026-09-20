<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd1p3qxtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cd1p3qxtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:button-outline" /></template>
