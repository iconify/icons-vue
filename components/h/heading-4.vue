<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9e7o7bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9e7o7bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-4" /></template>
