<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc8lrbwyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zc8lrbwyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-protection" /></template>
