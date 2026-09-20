<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg5eosgbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg5eosgbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-variant-outline" /></template>
