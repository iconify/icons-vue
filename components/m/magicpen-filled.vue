<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0nolhb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0nolhb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:magicpen-filled" /></template>
