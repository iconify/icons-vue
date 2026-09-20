<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tat7ojpcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tat7ojpcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:crowdin" /></template>
