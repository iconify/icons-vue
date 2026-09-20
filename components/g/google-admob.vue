<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byze8w0xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byze8w0xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-admob" /></template>
