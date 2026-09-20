<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8-iphu6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8-iphu6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apple-fill" /></template>
