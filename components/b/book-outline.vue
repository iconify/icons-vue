<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e42s7434d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e42s7434d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-outline" /></template>
