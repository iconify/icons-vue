<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znong8deo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znong8deo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:divide" /></template>
