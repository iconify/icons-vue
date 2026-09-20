<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9wqu8b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9wqu8b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dumbbells2" /></template>
