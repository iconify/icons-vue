<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5q30_6zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5q30_6zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-lightroom-solid" /></template>
