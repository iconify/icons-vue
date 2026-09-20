<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b76ej6sry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b76ej6sry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:biscuit-lock" /></template>
