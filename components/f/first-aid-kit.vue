<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1n15habz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1n15habz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:first-aid-kit" /></template>
