<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb3nn5obp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb3nn5obp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-wrap-tight" /></template>
