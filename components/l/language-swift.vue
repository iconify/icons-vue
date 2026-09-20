<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de04vvcjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de04vvcjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-swift" /></template>
