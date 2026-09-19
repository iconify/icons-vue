<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0ovz2bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ovz2bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:house" /></template>
