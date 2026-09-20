<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4a0k1k5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4a0k1k5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dunzo" /></template>
