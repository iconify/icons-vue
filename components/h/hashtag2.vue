<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2lcv-sqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2lcv-sqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hashtag2" /></template>
