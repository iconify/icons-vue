<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4fs-vakd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4fs-vakd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bring-front" /></template>
