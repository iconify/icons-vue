<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjah9mb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pjah9mb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:filter" /></template>
