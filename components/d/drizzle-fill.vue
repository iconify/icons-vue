<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dix090bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dix090bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drizzle-fill" /></template>
