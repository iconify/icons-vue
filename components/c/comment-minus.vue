<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwfaqfb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwfaqfb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:comment-minus" /></template>
