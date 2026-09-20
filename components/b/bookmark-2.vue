<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el1a2nwhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="el1a2nwhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-2" /></template>
