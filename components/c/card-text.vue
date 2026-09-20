<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu1x-2owc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu1x-2owc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-text" /></template>
