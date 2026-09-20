<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niwqy6-id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niwqy6-id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:color-swatch-filled" /></template>
