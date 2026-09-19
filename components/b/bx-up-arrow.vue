<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go63bd4jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go63bd4jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-up-arrow" /></template>
