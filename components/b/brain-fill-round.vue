<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfy7pyfja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfy7pyfja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brain-fill-round" /></template>
