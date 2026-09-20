<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3a-zkbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3a-zkbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:clipboard-plus" /></template>
