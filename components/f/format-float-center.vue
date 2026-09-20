<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bilus0bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bilus0bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-float-center" /></template>
