<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn76f6a6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn76f6a6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-solid" /></template>
