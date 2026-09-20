<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqkw6gb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqkw6gb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:document-location-filled" /></template>
