<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzp235ura.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzp235ura"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:edge-style" /></template>
