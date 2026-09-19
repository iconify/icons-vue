<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4pca5byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4pca5byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-devere" /></template>
