<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w66qzd0ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w66qzd0ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:archive-filled" /></template>
