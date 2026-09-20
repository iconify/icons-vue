<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiqcs5z8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiqcs5z8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arena" /></template>
